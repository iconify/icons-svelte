<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohbpjk02c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":630,"height":700};
const content = `<path class="ohbpjk02c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:arrow-down" {...props}></Icon>
