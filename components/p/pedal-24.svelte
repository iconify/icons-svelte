<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mefg8obex.css';
import '../../css/i/ittidrwdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mefg8obex"/><path clip-rule="evenodd" class="ittidrwdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pedal-24" {...props}></Icon>
