<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3h0_zb2o.css';
import '../../css/n/n3pz-6bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3h0_zb2o"/><path class="n3pz-6bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-minimalistic-bold" {...props}></Icon>
