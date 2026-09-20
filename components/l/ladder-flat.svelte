<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj6a17ihb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tj6a17ihb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:ladder-flat" {...props}></Icon>
