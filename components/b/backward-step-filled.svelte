<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af2sdjjic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af2sdjjic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:backward-step-filled" {...props}></Icon>
