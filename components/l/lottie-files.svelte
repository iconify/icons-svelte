<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw7ii9h6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw7ii9h6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:lottie-files" {...props}></Icon>
