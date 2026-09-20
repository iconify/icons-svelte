<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zxww0ab5s.css';
import '../../css/u/ubwtmclzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zxww0ab5s"/><path class="ubwtmclzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:copy-duotone" {...props}></Icon>
