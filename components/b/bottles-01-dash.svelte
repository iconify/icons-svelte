<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4bbxcc8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o4bbxcc8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bottles-01-dash" {...props}></Icon>
