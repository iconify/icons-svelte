<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgelptg3x.css';
import '../../css/n/n3pz-6bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgelptg3x"/><path class="n3pz-6bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-minimalistic-bold" {...props}></Icon>
