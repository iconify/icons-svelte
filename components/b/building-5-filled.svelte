<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x969onb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x969onb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:building-5-filled" {...props}></Icon>
