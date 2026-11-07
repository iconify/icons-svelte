<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io95umbud.css';
import '../../css/v/vr0cnhd_c.css';
import '../../css/d/dc6a51hpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io95umbud"/><path clip-rule="evenodd" class="vr0cnhd_c"/><path class="dc6a51hpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:adhesive-plaster-bold" {...props}></Icon>
