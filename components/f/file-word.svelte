<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en-rpj4we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en-rpj4we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-word" {...props}></Icon>
