<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v74tltshr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fpvc0x2ta.css';
import '../../css/a/a-qyfacks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary v74tltshr"/><g class="dt0cm9dhy primary"><path class="fpvc0x2ta"/><path class="a-qyfacks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:play-pause-duo" {...props}></Icon>
