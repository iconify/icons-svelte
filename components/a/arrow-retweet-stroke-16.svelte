<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vry7g_bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vry7g_bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-retweet-stroke-16" {...props}></Icon>
