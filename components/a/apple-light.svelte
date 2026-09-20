<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc-1-6brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":814,"height":1000};
const content = `<path class="nc-1-6brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apple-light" {...props}></Icon>
