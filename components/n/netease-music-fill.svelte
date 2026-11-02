<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw7ll75ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw7ll75ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:netease-music-fill" {...props}></Icon>
