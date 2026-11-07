<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4x-dibbg.css';
import '../../css/p/pjg7f5xap.css';
import '../../css/q/qz1qozbrv.css';
import '../../css/u/uomfvrbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4x-dibbg"/><path clip-rule="evenodd" class="pjg7f5xap"/><path class="qz1qozbrv"/><path class="uomfvrbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-slider-bold" {...props}></Icon>
