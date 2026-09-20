<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykq264b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykq264b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-g" {...props}></Icon>
