<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/asyphl89v.css';
import '../../css/h/hd0f2xmdw.css';
import '../../css/g/gcrp6yu8e.css';
import '../../css/f/fafv2obpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="asyphl89v"/><path class="hd0f2xmdw"/><path class="gcrp6yu8e"/><path class="fafv2obpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:copilotkit" {...props}></Icon>
