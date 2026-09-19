<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgvrc_86n.css';
import '../../css/k/knx35mxfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgvrc_86n"/><path class="knx35mxfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:donate-heart" {...props}></Icon>
