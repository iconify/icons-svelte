<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjse0jekj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yjse0jekj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:nature-fire" {...props}></Icon>
