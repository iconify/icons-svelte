<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj0gtbbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj0gtbbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:facebook-logo-1" {...props}></Icon>
