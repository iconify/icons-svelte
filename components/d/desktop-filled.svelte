<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql6c7ubyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql6c7ubyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:desktop-filled" {...props}></Icon>
