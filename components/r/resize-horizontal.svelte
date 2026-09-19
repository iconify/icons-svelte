<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6d7aiw7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i6d7aiw7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:resize-horizontal" {...props}></Icon>
