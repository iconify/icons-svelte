<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dir5a1bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dir5a1bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:options" {...props}></Icon>
