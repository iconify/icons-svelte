<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8_7k8mch.css';
import '../../css/f/fd4fpfb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f8_7k8mch"/><path class="fd4fpfb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-csv" {...props}></Icon>
