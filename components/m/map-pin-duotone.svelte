<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uagohvbgi.css';
import '../../css/g/gl2l3xbkp.css';
import '../../css/a/aggqj-bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uagohvbgi"/><path class="gl2l3xbkp"/><path clip-rule="evenodd" class="aggqj-bka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-duotone" {...props}></Icon>
