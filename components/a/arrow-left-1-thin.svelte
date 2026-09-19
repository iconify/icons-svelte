<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-zxidb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-zxidb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-1-thin" {...props}></Icon>
