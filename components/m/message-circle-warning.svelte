<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixphaca2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixphaca2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-circle-warning" {...props}></Icon>
