<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9rq_swmq.css';
import '../../css/b/bhcwjtbdh.css';
import '../../css/y/y-ulyzb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9rq_swmq"/><path class="bhcwjtbdh"/><path class="y-ulyzb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:balloon-outline" {...props}></Icon>
