<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr85fxbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kr85fxbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-tc-plus-square" {...props}></Icon>
