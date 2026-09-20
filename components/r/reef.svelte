<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsdw_21te.css';
import '../../css/i/ihcr3ob1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsdw_21te"/><path class="ihcr3ob1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:reef" {...props}></Icon>
