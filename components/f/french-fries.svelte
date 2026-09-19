<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg1a5jd7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lg1a5jd7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:french-fries" {...props}></Icon>
