<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw7inrb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tw7inrb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cli-outline" {...props}></Icon>
