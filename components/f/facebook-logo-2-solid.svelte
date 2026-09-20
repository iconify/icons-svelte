<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9aqz85-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9aqz85-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:facebook-logo-2-solid" {...props}></Icon>
