<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yybd16bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yybd16bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:panel-ipc-fail" {...props}></Icon>
