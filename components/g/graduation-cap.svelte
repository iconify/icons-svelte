<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp7zgxjuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp7zgxjuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:graduation-cap" {...props}></Icon>
