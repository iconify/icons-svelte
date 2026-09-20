<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgb3rhbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgb3rhbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:retweet-logo-solid" {...props}></Icon>
