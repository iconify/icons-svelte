<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufflo816n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufflo816n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gamepad-directional" {...props}></Icon>
