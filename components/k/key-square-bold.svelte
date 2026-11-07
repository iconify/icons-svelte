<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdzkjibvl.css';
import '../../css/e/e4qlnbc0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdzkjibvl"/><path clip-rule="evenodd" class="e4qlnbc0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-square-bold" {...props}></Icon>
