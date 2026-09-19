<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6geo1bkk.css';
import '../../css/d/drbv3ibqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h6geo1bkk"/><path class="drbv3ibqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chat" {...props}></Icon>
