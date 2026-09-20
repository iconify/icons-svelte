<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g7_hdonmj.css';
import '../../css/z/z6j86kbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g7_hdonmj"/><path class="z6j86kbeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-next-duotone" {...props}></Icon>
