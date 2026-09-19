<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9kzb9bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g9kzb9bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rocket" {...props}></Icon>
