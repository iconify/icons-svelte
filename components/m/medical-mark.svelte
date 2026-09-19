<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wonky8b2c.css';
import '../../css/f/fskaxzzpg.css';
import '../../css/k/kinc7xbvh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwoSM3bAQ"><g class="ufeehvblu"><path class="wonky8b2c"/><path class="fskaxzzpg"/><path class="kinc7xbvh"/></g></mask></defs><path mask="url(#SVGwoSM3bAQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:medical-mark" {...props}></Icon>
