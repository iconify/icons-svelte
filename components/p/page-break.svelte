<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j90vc2a6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j90vc2a6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:page-break" {...props}></Icon>
