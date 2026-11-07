<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esxisibaw.css';
import '../../css/u/ud65eiioe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="esxisibaw"/><path class="ud65eiioe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbon-bold-duotone" {...props}></Icon>
