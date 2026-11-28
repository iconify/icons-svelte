<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atmzkckly.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtipehbld.css';
import '../../css/w/w-t6mzbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atmzkckly secondary"/><g class="dt0cm9dhy primary"><path class="gtipehbld"/><path class="w-t6mzbal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-pen-duo" {...props}></Icon>
