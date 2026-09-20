<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giw43fzcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giw43fzcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:corner-up-left" {...props}></Icon>
