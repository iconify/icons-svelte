<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/j/j_ypwpb7a.css';
import '../../css/i/i-rf7x3rz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYBDePw3h"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="j_ypwpb7a"/><path class="i-rf7x3rz"/></g></mask></defs><path mask="url(#SVGYBDePw3h)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:left-bar" {...props}></Icon>
