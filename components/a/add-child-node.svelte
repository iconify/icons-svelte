<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq6tgxbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jq6tgxbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:add-child-node" {...props}></Icon>
