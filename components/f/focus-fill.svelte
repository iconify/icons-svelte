<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5qd9wgmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5qd9wgmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:focus-fill" {...props}></Icon>
