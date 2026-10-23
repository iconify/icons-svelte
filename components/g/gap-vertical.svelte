<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r36lvjb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r36lvjb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gap-vertical" {...props}></Icon>
