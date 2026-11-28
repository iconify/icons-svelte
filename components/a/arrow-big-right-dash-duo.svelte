<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ews8m83sk.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zde---bwt.css';
import '../../css/e/esbmfdf6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ews8m83sk secondary"/><g class="dt0cm9dhy primary"><path class="zde---bwt"/><path class="esbmfdf6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-right-dash-duo" {...props}></Icon>
