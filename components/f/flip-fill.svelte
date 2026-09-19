<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdo2_9rnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdo2_9rnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:flip-fill" {...props}></Icon>
