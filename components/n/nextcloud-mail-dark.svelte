<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm9_89bsm.css';
import '../../css/z/z6-pcfb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xm9_89bsm"/><path class="z6-pcfb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-mail-dark" {...props}></Icon>
