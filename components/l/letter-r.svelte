<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezy1ainvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezy1ainvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-r" {...props}></Icon>
