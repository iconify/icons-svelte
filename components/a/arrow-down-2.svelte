<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syz0a_bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syz0a_bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-2" {...props}></Icon>
