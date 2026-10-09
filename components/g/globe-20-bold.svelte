<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0oa-qzdz.css';
import '../../css/a/aifrzk3-i.css';
import '../../css/a/atyqr0b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="aifrzk3-i"/><path class="atyqr0b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:globe-20-bold" {...props}></Icon>
