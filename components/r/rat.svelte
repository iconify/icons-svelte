<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaax8ab6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gaax8ab6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rat" {...props}></Icon>
