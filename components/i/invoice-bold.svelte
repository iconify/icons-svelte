<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_y7vvb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_y7vvb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:invoice-bold" {...props}></Icon>
