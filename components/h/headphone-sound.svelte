<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h5v6uobzb.css';
import '../../css/e/ewi85glah.css';
import '../../css/f/frzjyvvrk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGERWYaeKe"><g class="ft5dv1b6b"><path class="h5v6uobzb"/><path class="ewi85glah"/><path class="frzjyvvrk"/></g></mask></defs><path mask="url(#SVGERWYaeKe)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:headphone-sound" {...props}></Icon>
