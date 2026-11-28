<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4wx-tw7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4wx-tw7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clapperboard-play" {...props}></Icon>
