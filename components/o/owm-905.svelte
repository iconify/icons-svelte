<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywx6ye69t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ywx6ye69t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-905" {...props}></Icon>
