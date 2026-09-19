<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nffh7rbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nffh7rbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-right-box-outline" {...props}></Icon>
