<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1ieycbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n1ieycbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-reaching-up" {...props}></Icon>
