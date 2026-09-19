<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/f/f7orvpbwy.css';
import '../../css/i/i9aqj_b9h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGL6k8IccK"><g class="ufeehvblu"><path class="f7orvpbwy"/><path class="i9aqj_b9h"/></g></mask></defs><path mask="url(#SVGL6k8IccK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:platte" {...props}></Icon>
