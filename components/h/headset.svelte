<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7ql57b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c7ql57b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:headset" {...props}></Icon>
