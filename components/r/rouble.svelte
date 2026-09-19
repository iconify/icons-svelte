<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3sxunm-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="v3sxunm-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rouble" {...props}></Icon>
