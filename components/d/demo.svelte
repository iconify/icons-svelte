<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izajwurpr.css';
import '../../css/g/g24buwbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="izajwurpr"/><path class="g24buwbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:demo" {...props}></Icon>
