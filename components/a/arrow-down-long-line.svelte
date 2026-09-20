<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql9f2lbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql9f2lbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-long-line" {...props}></Icon>
