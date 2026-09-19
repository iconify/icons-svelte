<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vpqs4v0fe.css';
import '../../css/g/gn-k8rb_d.css';
import '../../css/n/nu33h_bty.css';
import '../../css/c/cm-ruxshm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="vpqs4v0fe"/><path class="gn-k8rb_d"/><path class="nu33h_bty"/><path class="cm-ruxshm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:etc" {...props}></Icon>
