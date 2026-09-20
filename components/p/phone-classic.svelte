<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxz-pzbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxz-pzbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-classic" {...props}></Icon>
