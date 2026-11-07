<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1hxn4bwg.css';
import '../../css/u/ud-yki_gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a1hxn4bwg"/><path class="ud-yki_gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dropper-minimalistic-bold" {...props}></Icon>
