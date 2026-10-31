<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3x4e39zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y3x4e39zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-box-gabled-building-with-chimney-and-door" {...props}></Icon>
