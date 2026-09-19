<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xoh_d-6_k.css';
import '../../css/j/jm2mnjbyt.css';
import '../../css/v/vo0s0d-xn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUUJ2XbXa"><g class="ufeehvblu"><path class="xoh_d-6_k"/><path class="jm2mnjbyt"/><path class="vo0s0d-xn"/></g></mask></defs><path mask="url(#SVGUUJ2XbXa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:blackboard" {...props}></Icon>
