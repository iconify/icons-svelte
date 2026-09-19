<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfar3hb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="hfar3hb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:magnet" {...props}></Icon>
