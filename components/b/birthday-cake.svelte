<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cl137rc4n.css';
import '../../css/m/m7erot3eb.css';
import '../../css/j/j_shnj9av.css';
import '../../css/h/ho-dy2vqv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkrEjI5dA"><g class="ft5dv1b6b"><path class="cl137rc4n"/><path class="m7erot3eb"/><path class="j_shnj9av"/><path class="ho-dy2vqv"/></g></mask></defs><path mask="url(#SVGkrEjI5dA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:birthday-cake" {...props}></Icon>
