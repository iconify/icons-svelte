<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvmmamb2n.css';
import '../../css/k/kiom4-bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvmmamb2n"/><path class="kiom4-bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-pin-bold" {...props}></Icon>
