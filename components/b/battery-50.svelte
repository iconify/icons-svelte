<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io_iyrrsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io_iyrrsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-50" {...props}></Icon>
