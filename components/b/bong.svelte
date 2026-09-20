<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uipj-oqpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uipj-oqpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bong" {...props}></Icon>
