<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6jby-byc.css';
import '../../css/m/m32igq_in.css';
import '../../css/k/kf81dz8xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6jby-byc"/><path class="m32igq_in"/><path class="kf81dz8xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:backofenvelope" {...props}></Icon>
