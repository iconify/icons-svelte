<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fro30fydk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fro30fydk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:loom-logo" {...props}></Icon>
