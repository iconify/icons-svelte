<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm92uhb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="xm92uhb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mastercard" {...props}></Icon>
