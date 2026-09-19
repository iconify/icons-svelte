<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzs7albyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzs7albyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:reduce" {...props}></Icon>
