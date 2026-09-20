<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u956u2x8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u956u2x8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:microsoft-windows-logo-1-block" {...props}></Icon>
