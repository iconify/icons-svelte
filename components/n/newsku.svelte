<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkioc6b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kkioc6b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newsku" {...props}></Icon>
