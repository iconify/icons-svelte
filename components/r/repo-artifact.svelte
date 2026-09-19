<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxlaslbqv.css';
import '../../css/f/f-sg0db9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oxlaslbqv"/><path class="f-sg0db9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:repo-artifact" {...props}></Icon>
