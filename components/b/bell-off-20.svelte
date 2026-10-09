<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7lbhgb_q.css';
import '../../css/i/iffp3wblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7lbhgb_q"/><path class="iffp3wblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-off-20" {...props}></Icon>
