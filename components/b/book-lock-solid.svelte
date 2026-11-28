<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjcpelbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjcpelbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-lock-solid" {...props}></Icon>
