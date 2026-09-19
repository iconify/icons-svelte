<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7oawiavk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t7oawiavk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mcap" {...props}></Icon>
