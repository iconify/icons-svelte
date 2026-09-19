<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7gd7dfck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q7gd7dfck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pen-to-square" {...props}></Icon>
