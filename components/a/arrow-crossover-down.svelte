<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjo9w027v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yjo9w027v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-crossover-down" {...props}></Icon>
