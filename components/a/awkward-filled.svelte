<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7xnsacay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7xnsacay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:awkward-filled" {...props}></Icon>
