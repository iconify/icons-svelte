<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz_y34baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz_y34baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:etc-vertical" {...props}></Icon>
