<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyi9sg69u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="oyi9sg69u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:escalator" {...props}></Icon>
