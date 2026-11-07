<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ourjeh54g.css';
import '../../css/f/fgil9vbxo.css';
import '../../css/i/i7qoswbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ourjeh54g"/><path clip-rule="evenodd" class="fgil9vbxo"/><path clip-rule="evenodd" class="i7qoswbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-10-seconds-back-bold-duotone" {...props}></Icon>
