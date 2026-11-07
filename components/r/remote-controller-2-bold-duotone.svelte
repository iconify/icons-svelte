<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be24kjn_m.css';
import '../../css/k/k85rg8b0j.css';
import '../../css/k/ky3o20byt.css';
import '../../css/p/ps2m0xfqt.css';
import '../../css/h/h3x8wxboy.css';
import '../../css/m/mybsyle5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be24kjn_m"/><path class="k85rg8b0j"/><path class="ky3o20byt"/><path class="ps2m0xfqt"/><path class="h3x8wxboy"/><path clip-rule="evenodd" class="mybsyle5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remote-controller-2-bold-duotone" {...props}></Icon>
