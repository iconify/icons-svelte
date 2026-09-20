<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9krgsina.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="w9krgsina"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rewind" {...props}></Icon>
