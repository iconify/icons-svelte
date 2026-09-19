<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8v77ac5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c8v77ac5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:glimmer" {...props}></Icon>
