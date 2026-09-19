<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdj57bb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="jdj57bb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:power" {...props}></Icon>
