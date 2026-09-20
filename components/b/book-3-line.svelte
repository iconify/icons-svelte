<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wia3r3wym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wia3r3wym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-3-line" {...props}></Icon>
