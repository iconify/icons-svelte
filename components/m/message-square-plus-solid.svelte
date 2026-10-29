<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpu66u8hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpu66u8hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square-plus-solid" {...props}></Icon>
