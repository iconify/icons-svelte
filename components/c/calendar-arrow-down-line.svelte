<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw7442-qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw7442-qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-arrow-down-line" {...props}></Icon>
