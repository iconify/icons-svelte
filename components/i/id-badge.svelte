<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1ptg-o8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i1ptg-o8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:id-badge" {...props}></Icon>
