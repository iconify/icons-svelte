<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj0om06rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gj0om06rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:blue-circle" {...props}></Icon>
