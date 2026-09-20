<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpt2--6uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jpt2--6uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:check" {...props}></Icon>
