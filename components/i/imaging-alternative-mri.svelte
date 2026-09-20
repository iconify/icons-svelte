<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhnxvf8sx.css';
import '../../css/b/br4kpx8po.css';
import '../../css/w/wnu_u707u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="mhnxvf8sx"/><path class="br4kpx8po"/><path class="wnu_u707u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:imaging-alternative-mri" {...props}></Icon>
