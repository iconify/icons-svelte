<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p131fac8n.css';
import '../../css/p/piu__0p4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p131fac8n"/><path class="piu__0p4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:book-duotone" {...props}></Icon>
