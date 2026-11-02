<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv8zkgwyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv8zkgwyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hop-2-fill" {...props}></Icon>
