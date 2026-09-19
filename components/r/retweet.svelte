<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj8wdqbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cj8wdqbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:retweet" {...props}></Icon>
