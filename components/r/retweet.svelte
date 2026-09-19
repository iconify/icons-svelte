<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2bw7kbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1360,"height":1000};
const content = `<path class="l2bw7kbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:retweet" {...props}></Icon>
