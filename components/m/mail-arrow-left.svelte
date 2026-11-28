<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v7v0zjbzo.css';
import '../../css/a/aivyodbgw.css';
import '../../css/j/jfq8r8bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v7v0zjbzo"/><path class="aivyodbgw"/><path class="jfq8r8bvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-arrow-left" {...props}></Icon>
