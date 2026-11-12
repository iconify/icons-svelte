<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi7zzdbka.css';
import '../../css/d/d_cc7c6xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qi7zzdbka"/><path class="d_cc7c6xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lingva-translate-light" {...props}></Icon>
