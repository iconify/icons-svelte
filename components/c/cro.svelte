<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0ql8sb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0ql8sb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cro" {...props}></Icon>
