<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ik1jx-bvn.css';
import '../../css/o/o_ke7ac_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ik1jx-bvn"/><path class="o_ke7ac_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:home-detailed-duotone" {...props}></Icon>
