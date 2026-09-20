<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfcb0sdvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mfcb0sdvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-medical" {...props}></Icon>
