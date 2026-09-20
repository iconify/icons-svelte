<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugcmfac-c.css';
import '../../css/n/nqeft6d_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="ugcmfac-c"/><path class="nqeft6d_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:fire-extinguisher" {...props}></Icon>
