<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz7-w4vmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz7-w4vmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:magnify" {...props}></Icon>
