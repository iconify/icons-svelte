<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o73n4sb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o73n4sb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:green-circle" {...props}></Icon>
