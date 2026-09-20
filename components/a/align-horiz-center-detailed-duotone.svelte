<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pex2gnv1d.css';
import '../../css/o/orey5jilx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pex2gnv1d"/><path class="orey5jilx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-horiz-center-detailed-duotone" {...props}></Icon>
