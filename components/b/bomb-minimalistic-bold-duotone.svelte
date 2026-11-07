<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5kplybjs.css';
import '../../css/g/g7yg0ac0f.css';
import '../../css/q/qevi5wb1d.css';
import '../../css/d/dlqpvfanl.css';
import '../../css/v/vsfmdqbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5kplybjs"/><path class="g7yg0ac0f"/><path class="qevi5wb1d"/><path class="dlqpvfanl"/><path class="vsfmdqbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bomb-minimalistic-bold-duotone" {...props}></Icon>
