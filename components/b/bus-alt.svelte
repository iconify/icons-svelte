<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he1sdb3fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="he1sdb3fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bus-alt" {...props}></Icon>
