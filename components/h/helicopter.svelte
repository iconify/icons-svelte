<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waxbr3bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waxbr3bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:helicopter" {...props}></Icon>
