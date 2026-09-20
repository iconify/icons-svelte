<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1i-wyf2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1i-wyf2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-4-fill" {...props}></Icon>
