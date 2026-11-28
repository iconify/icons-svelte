<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dh1ukibik.css';
import '../../css/a/a4jv2kb1u.css';
import '../../css/u/uni0xsbld.css';
import '../../css/s/s6d4vbbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="dh1ukibik"/><path class="a4jv2kb1u"/><path class="uni0xsbld"/><path class="s6d4vbbae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bamboo" {...props}></Icon>
