<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhwetz1ra.css';
import '../../css/x/xrvh-kbwe.css';
import '../../css/u/u3rfhw5gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rhwetz1ra"/><path class="xrvh-kbwe"/><path class="u3rfhw5gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calico-dark" {...props}></Icon>
