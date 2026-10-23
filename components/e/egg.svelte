<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og45v3brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og45v3brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:egg" {...props}></Icon>
