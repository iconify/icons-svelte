<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qclgze96h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qclgze96h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevrons-right-left" {...props}></Icon>
