<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh9k4dl3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fh9k4dl3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-paper" {...props}></Icon>
