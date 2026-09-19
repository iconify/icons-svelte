<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1m0pe8ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a1m0pe8ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-vis-2" {...props}></Icon>
