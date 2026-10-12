<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzpnafokc.css';
import '../../css/s/sb1oe8_aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vzpnafokc"/><path class="sb1oe8_aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-whatsapp-20" {...props}></Icon>
