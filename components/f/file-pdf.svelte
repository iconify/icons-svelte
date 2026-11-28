<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cmwiddbxv.css';
import '../../css/h/hji4qyb_f.css';
import '../../css/u/ufm4c-buh.css';
import '../../css/r/rlf1jguyc.css';
import '../../css/v/vqln7qj6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cmwiddbxv"/><path class="hji4qyb_f"/><path class="ufm4c-buh"/><path class="rlf1jguyc"/><path class="vqln7qj6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-pdf" {...props}></Icon>
