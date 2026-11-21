<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi6y65ble.css';
import '../../css/j/j2lg5bcnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi6y65ble"/><path class="j2lg5bcnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:funnel-x-filled" {...props}></Icon>
