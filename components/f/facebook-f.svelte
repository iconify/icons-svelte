<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upfjltgae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upfjltgae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:facebook-f" {...props}></Icon>
