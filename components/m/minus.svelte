<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oasy1vb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oasy1vb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:minus" {...props}></Icon>
