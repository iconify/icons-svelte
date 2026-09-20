<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxj4q7bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxj4q7bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:microsoft" {...props}></Icon>
