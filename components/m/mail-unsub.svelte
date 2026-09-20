<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7l5kub7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w7l5kub7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:mail-unsub" {...props}></Icon>
