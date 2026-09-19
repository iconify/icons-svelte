<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clchc7ilh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="clchc7ilh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:dining-room" {...props}></Icon>
