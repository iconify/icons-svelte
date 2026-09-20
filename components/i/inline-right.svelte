<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfq67mvgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hfq67mvgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:inline-right" {...props}></Icon>
