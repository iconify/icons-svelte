<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqyxmsbpe.css';
import '../../css/l/lxfy0olss.css';
import '../../css/d/d2oowm1mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yqyxmsbpe"/><path class="lxfy0olss"/><path class="d2oowm1mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-monitor-dark" {...props}></Icon>
