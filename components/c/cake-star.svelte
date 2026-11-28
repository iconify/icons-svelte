<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg1yy-brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg1yy-brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cake-star" {...props}></Icon>
