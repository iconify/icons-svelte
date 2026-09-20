<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlmq6jb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nlmq6jb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:book-outline" {...props}></Icon>
