<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4si8vbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4si8vbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-circle" {...props}></Icon>
