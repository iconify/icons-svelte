<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q40yrzbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1280};
const content = `<path class="q40yrzbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:retweet" {...props}></Icon>
