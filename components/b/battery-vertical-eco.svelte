<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0x3zvd3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0x3zvd3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-eco" {...props}></Icon>
