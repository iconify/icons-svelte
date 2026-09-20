<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgj48d40s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgj48d40s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deezer-logo-block" {...props}></Icon>
