<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq6e7rs9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq6e7rs9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:diamond" {...props}></Icon>
