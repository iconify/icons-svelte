<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo-rxrb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oo-rxrb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-retweet-fill-16" {...props}></Icon>
