<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpvo_gb0n.css';
import '../../css/a/akoivubxv.css';
import '../../css/e/eqwsh3bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpvo_gb0n"/><path class="akoivubxv"/><path clip-rule="evenodd" class="eqwsh3bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-left-bold-duotone" {...props}></Icon>
