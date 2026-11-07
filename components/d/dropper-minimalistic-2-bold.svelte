<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7d917_2k.css';
import '../../css/u/ud-yki_gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l7d917_2k"/><path class="ud-yki_gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dropper-minimalistic-2-bold" {...props}></Icon>
