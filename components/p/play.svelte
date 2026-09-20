<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq9f_m1cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq9f_m1cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:play" {...props}></Icon>
