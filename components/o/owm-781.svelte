<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnioaab0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="fnioaab0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-781" {...props}></Icon>
