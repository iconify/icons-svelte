<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/inbsb8b-e.css';
import '../../css/u/uiypogtcm.css';
import '../../css/m/mp6nn9g5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="inbsb8b-e"/><path class="uiypogtcm"/><path class="mp6nn9g5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-markdown" {...props}></Icon>
