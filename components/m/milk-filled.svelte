<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmya2ccpk.css';
import '../../css/g/gg1luzbnt.css';
import '../../css/t/t_to33i-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmya2ccpk"/><path clip-rule="evenodd" class="gg1luzbnt"/><rect class="t_to33i-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:milk-filled" {...props}></Icon>
