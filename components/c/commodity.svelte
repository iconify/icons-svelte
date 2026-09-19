<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fe8ov1blm.css';
import '../../css/n/ny-0gfb3p.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8xZFKcWH"><g class="ufeehvblu"><path class="fe8ov1blm"/><path class="ny-0gfb3p"/></g></mask></defs><path mask="url(#SVG8xZFKcWH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:commodity" {...props}></Icon>
