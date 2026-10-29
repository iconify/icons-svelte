<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9a92jqlz.css';
import '../../css/z/zbfvni7ud.css';
import '../../css/w/w5v6gnb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k z9a92jqlz"/><path class="wm-k zbfvni7ud"/><path class="w5v6gnb2d wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:rainbow" {...props}></Icon>
