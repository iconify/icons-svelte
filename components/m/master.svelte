<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j4azcmbmn.css';
import '../../css/m/mlfvy1b-f.css';
import '../../css/m/mma5cub1k.css';
import '../../css/i/i13dvsb0b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6p48Ec4M"><g class="ft5dv1b6b"><path class="j4azcmbmn"/><rect class="mlfvy1b-f"/><path class="mma5cub1k"/><circle class="i13dvsb0b"/></g></mask></defs><path mask="url(#SVG6p48Ec4M)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:master" {...props}></Icon>
