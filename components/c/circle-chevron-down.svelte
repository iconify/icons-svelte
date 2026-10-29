<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csivk-nbx.css';
import '../../css/z/znu966bzc.css';
import '../../css/z/zjm716l0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csivk-nbx wm-k"/><path class="wm-a znu966bzc"/><path class="wm-a zjm716l0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle-chevron-down" {...props}></Icon>
