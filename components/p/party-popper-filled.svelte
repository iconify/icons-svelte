<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emus6-b1j.css';
import '../../css/q/qrb2onfcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emus6-b1j"/><path class="qrb2onfcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:party-popper-filled" {...props}></Icon>
