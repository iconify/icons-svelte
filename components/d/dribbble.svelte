<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndp0sdb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ndp0sdb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:dribbble" {...props}></Icon>
