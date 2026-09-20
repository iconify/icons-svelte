<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_3tac-mi.css';
import '../../css/i/iebp_9cqm.css';
import '../../css/y/ygp2y4lsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":448};
const content = `<defs><path id="SVGx22VTcBv" class="v_3tac-mi"/></defs><g class="iebp_9cqm"><use href="#SVGx22VTcBv"/><use href="#SVGx22VTcBv"/><path class="ygp2y4lsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:intlayer-dark" {...props}></Icon>
