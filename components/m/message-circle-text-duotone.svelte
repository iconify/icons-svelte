<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ux9cb8bsw.css';
import '../../css/y/yo4cusbpd.css';
import '../../css/l/ldaeqpbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ux9cb8bsw"/><path class="yo4cusbpd"/><path class="ldaeqpbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-text-duotone" {...props}></Icon>
