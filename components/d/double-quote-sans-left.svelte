<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys01xebuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ys01xebuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:double-quote-sans-left" {...props}></Icon>
