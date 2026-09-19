<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1uo0nbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q1uo0nbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-quote-fill" {...props}></Icon>
