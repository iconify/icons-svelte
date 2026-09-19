<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se_do7boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="se_do7boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:people-robbery" {...props}></Icon>
