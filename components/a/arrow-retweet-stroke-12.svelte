<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sib82zv6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sib82zv6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-retweet-stroke-12" {...props}></Icon>
