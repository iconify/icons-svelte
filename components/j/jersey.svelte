<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb889bbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="xb889bbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:jersey" {...props}></Icon>
