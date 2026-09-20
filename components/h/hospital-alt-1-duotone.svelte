<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ilflw-89y.css';
import '../../css/f/fnpn8kb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ilflw-89y"/><path class="fnpn8kb8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hospital-alt-1-duotone" {...props}></Icon>
