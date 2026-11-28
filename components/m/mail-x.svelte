<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v7v0zjbzo.css';
import '../../css/a/aivyodbgw.css';
import '../../css/r/rqbnl5bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v7v0zjbzo"/><path class="aivyodbgw"/><path class="rqbnl5bte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-x" {...props}></Icon>
