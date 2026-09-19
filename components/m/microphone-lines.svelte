<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9w3olbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c9w3olbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:microphone-lines" {...props}></Icon>
