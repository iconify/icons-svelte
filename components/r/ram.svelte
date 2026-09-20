<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbp5r2bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbp5r2bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ram" {...props}></Icon>
