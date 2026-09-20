<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veznnoyuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veznnoyuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:retweet-logo" {...props}></Icon>
