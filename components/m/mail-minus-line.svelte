<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am04dyb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am04dyb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-minus-line" {...props}></Icon>
