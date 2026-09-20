<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyx7_x3zo.css';
import '../../css/a/a6dsmibvs.css';
import '../../css/u/u9-lmsbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iyx7_x3zo"/><path class="a6dsmibvs"/><path class="u9-lmsbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pyload" {...props}></Icon>
