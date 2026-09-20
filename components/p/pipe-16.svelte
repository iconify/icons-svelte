<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl9c0ib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yl9c0ib4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pipe-16" {...props}></Icon>
