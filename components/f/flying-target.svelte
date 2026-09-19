<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovw2lp1zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ovw2lp1zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flying-target" {...props}></Icon>
