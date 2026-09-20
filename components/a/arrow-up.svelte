<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdty62s8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bdty62s8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:arrow-up" {...props}></Icon>
