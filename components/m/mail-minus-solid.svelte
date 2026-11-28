<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkd9d5s_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkd9d5s_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-minus-solid" {...props}></Icon>
