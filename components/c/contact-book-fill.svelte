<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sktthrbsc.css';
import '../../css/c/cxl-8rb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sktthrbsc"/><path class="cxl-8rb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:contact-book-fill" {...props}></Icon>
