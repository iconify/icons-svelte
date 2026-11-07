<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udpk4tbla.css';
import '../../css/p/pob1i1ksy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udpk4tbla"/><path clip-rule="evenodd" class="pob1i1ksy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-charge-bold" {...props}></Icon>
