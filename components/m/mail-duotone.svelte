<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ytvgiibzk.css';
import '../../css/c/cll2n7u_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ytvgiibzk"/><path class="cll2n7u_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:mail-duotone" {...props}></Icon>
