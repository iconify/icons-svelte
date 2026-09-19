<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6srxhjli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":496};
const content = `<path class="b6srxhjli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cart" {...props}></Icon>
