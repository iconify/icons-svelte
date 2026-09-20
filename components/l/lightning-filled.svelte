<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_f49x26x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l_f49x26x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:lightning-filled" {...props}></Icon>
