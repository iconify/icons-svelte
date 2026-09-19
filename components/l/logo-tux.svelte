<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntr_u1-hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntr_u1-hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-tux" {...props}></Icon>
