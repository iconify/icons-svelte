<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki3qabcfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ki3qabcfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:open-book" {...props}></Icon>
