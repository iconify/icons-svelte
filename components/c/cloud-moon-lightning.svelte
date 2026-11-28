<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/imzldxsyv.css';
import '../../css/n/nbau5bnxf.css';
import '../../css/x/xbkcvubst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="imzldxsyv"/><path class="nbau5bnxf"/><path class="xbkcvubst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-moon-lightning" {...props}></Icon>
