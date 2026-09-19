<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2yhjhbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="l2yhjhbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:retweet" {...props}></Icon>
