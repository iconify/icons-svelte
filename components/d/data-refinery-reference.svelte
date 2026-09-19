<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uez273bbq.css';
import '../../css/h/hhu-8gb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uez273bbq"/><path class="hhu-8gb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-refinery-reference" {...props}></Icon>
