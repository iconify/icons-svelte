<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkss39bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkss39bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clockwise-2-fill" {...props}></Icon>
