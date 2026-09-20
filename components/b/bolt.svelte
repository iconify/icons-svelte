<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmr7w7n-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wmr7w7n-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bolt" {...props}></Icon>
