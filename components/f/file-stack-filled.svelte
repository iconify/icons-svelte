<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udjwmmbyu.css';
import '../../css/i/ily3ncazb.css';
import '../../css/m/mjwibbccu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udjwmmbyu"/><path class="ily3ncazb"/><path class="mjwibbccu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-stack-filled" {...props}></Icon>
