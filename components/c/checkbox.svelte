<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht-699b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht-699b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:checkbox" {...props}></Icon>
