<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkg-e7bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vkg-e7bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:checkout" {...props}></Icon>
