<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io0afsb9o.css';
import '../../css/n/np4wfjoyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="io0afsb9o"/><path class="np4wfjoyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cyclist" {...props}></Icon>
