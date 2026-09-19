<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsr384viw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsr384viw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-x-filled" {...props}></Icon>
