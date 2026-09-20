<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ytpix0bfj.css';
import '../../css/q/q7lnze67b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ytpix0bfj"/><path class="q7lnze67b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-duotone" {...props}></Icon>
