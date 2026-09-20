<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw4o7vbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw4o7vbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bandcamp-logo-2-solid" {...props}></Icon>
