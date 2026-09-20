<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6yo2cn0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":118,"height":27};
const content = `<path class="m6yo2cn0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paramount-light" {...props}></Icon>
