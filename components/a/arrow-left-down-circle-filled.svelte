<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcdd--2ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcdd--2ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-left-down-circle-filled" {...props}></Icon>
