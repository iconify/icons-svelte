<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0ojwh5bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ojwh5bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-captions-filled" {...props}></Icon>
