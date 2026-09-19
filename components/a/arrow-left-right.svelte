<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xct69xb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xct69xb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-left-right" {...props}></Icon>
