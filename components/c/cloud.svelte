<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf24k7b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cf24k7b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud" {...props}></Icon>
