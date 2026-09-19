<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1idh6b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k1idh6b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-retweet-fill-12" {...props}></Icon>
