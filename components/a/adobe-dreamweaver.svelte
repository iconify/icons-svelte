<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8o_qbc7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m8o_qbc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:adobe-dreamweaver" {...props}></Icon>
