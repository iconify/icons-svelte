<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afnpse13x.css';
import '../../css/n/n3zmfgmgx.css';
import '../../css/k/kcvmbebru.css';
import '../../css/l/l2igllydu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="afnpse13x"/><ellipse class="n3zmfgmgx"/><path class="kcvmbebru"/><path class="l2igllydu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cookedrice" {...props}></Icon>
