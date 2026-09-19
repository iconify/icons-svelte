<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhssn9pid.css';
import '../../css/i/iu35e1xme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhssn9pid"/><circle class="iu35e1xme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bitaxe-filled" {...props}></Icon>
