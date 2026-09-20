<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0e5g6bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0e5g6bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:foursquare-logo-solid" {...props}></Icon>
