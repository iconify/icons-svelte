<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijxhlnqvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijxhlnqvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:player-me-logo-block" {...props}></Icon>
