<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thbt_3blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thbt_3blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-volume-fill" {...props}></Icon>
