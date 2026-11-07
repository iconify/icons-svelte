<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv4_o-byj.css';
import '../../css/w/wzjbfwbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv4_o-byj"/><path clip-rule="evenodd" class="wzjbfwbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-round-bold" {...props}></Icon>
