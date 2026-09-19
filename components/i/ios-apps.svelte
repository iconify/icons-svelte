<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6b0lkikv.css';
import '../../css/i/ixx3zz-eq.css';
import '../../css/m/m1ue-3z0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z6b0lkikv"/><path class="ixx3zz-eq"/><path class="m1ue-3z0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-apps" {...props}></Icon>
