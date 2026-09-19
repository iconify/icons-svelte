<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/temjivdtd.css';
import '../../css/x/xsit_hb8q.css';
import '../../css/c/cj87lbbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="temjivdtd"/><path class="xsit_hb8q"/><path class="cj87lbbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-personadd-outline" {...props}></Icon>
