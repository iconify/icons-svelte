<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8xyuzbbe.css';
import '../../css/n/nha8y7oaq.css';
import '../../css/m/mp4ag1boz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGy4YSvdBO"><g class="ft5dv1b6b"><path class="h8xyuzbbe"/><path class="nha8y7oaq"/><path class="mp4ag1boz"/></g></mask></defs><path mask="url(#SVGy4YSvdBO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:instagram" {...props}></Icon>
