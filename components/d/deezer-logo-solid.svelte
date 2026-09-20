<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb4qzoycs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mb4qzoycs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deezer-logo-solid" {...props}></Icon>
