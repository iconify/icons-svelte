<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thb2hsbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thb2hsbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-s" {...props}></Icon>
