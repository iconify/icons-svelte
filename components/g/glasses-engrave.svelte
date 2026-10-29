<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/teyry0bvj.css';
import '../../css/h/h8t4uobjx.css';
import '../../css/e/eznhzablb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="teyry0bvj"/><path class="h8t4uobjx wm-shadow"/><path class="eznhzablb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:glasses-engrave" {...props}></Icon>
