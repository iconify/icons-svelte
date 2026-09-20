<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhcw76f0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhcw76f0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-news-logo-solid" {...props}></Icon>
