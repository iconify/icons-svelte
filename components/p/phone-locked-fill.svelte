<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1268k_zf.css';
import '../../css/y/ypft5mbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1268k_zf"/><path class="ypft5mbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-locked-fill" {...props}></Icon>
