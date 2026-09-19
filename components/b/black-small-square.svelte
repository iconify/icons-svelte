<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhx3ojbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zhx3ojbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:black-small-square" {...props}></Icon>
