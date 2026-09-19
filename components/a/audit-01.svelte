<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wfwd8y9av.css';
import '../../css/r/rhy2hmbom.css';
import '../../css/g/gxnq7z-rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wfwd8y9av"/><path class="rhy2hmbom"/><path class="gxnq7z-rv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:audit-01" {...props}></Icon>
