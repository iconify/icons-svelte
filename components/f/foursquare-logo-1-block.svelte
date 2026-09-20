<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gojyo4b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gojyo4b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:foursquare-logo-1-block" {...props}></Icon>
