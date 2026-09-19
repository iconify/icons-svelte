<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io_efktyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="io_efktyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-databand" {...props}></Icon>
