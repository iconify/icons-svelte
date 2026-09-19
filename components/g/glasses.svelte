<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lfu9081tj.css';
import '../../css/u/ukpkwrb3v.css';
import '../../css/i/il6_1tbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="lfu9081tj"/><circle class="ukpkwrb3v"/><path class="il6_1tbws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:glasses" {...props}></Icon>
