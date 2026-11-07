<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/urc5ue4jr.css';
import '../../css/x/x_757hbgu.css';
import '../../css/d/d5t0b286k.css';
import '../../css/m/my5268blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="urc5ue4jr"/><path class="x_757hbgu"/><path class="d5t0b286k"/><path class="my5268blj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-text-line-duotone" {...props}></Icon>
