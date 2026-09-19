<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb0l32b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b mb0l32b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gestures" {...props}></Icon>
