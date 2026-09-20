<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb1iwq_9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb1iwq_9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:camera" {...props}></Icon>
