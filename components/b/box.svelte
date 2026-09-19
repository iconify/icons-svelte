<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb4g-_b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pb4g-_b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:box" {...props}></Icon>
