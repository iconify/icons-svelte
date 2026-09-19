<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs-ujmdie.css';
import '../../css/f/fwixbousw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs-ujmdie"/><path class="fwixbousw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:exposure-filled" {...props}></Icon>
