<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5n51ntxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y5n51ntxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-agent" {...props}></Icon>
