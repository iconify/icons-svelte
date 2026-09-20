<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo-7ywbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lo-7ywbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-up-down-left-right" {...props}></Icon>
