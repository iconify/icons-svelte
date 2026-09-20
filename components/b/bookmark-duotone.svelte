<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nyaz_cbfa.css';
import '../../css/f/fvhd-bhku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="ft5dv1b6b"><path class="nyaz_cbfa"/><path class="fvhd-bhku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bookmark-duotone" {...props}></Icon>
