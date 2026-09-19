<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w5s4ij3iu.css';
import '../../css/z/z4a_2z-dy.css';
import '../../css/v/vpx938hem.css';
import '../../css/v/v_nzipb8v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGat6CjcGc"><g class="ft5dv1b6b"><path class="w5s4ij3iu"/><path class="z4a_2z-dy"/><path clip-rule="evenodd" class="vpx938hem"/><path class="v_nzipb8v"/></g></mask></defs><path mask="url(#SVGat6CjcGc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:brightness" {...props}></Icon>
