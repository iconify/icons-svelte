<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdrcr1l6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cdrcr1l6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:join-node" {...props}></Icon>
