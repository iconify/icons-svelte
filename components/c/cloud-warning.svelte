<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orupi1b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="orupi1b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cloud-warning" {...props}></Icon>
