<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmx8ijb7m.css';
import '../../css/i/ibya-7rop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmx8ijb7m"/><path class="ibya-7rop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:namebadge" {...props}></Icon>
