<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/w/w0mp90b1v.css';
import '../../css/s/sv05mfuxd.css';
import '../../css/d/d_ldgic0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="w0mp90b1v"/><path class="sv05mfuxd"/><path class="d_ldgic0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:keyboard-delete-button" {...props}></Icon>
