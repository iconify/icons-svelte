<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xilwagbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xilwagbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-off" {...props}></Icon>
