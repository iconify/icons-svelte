<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgv6h9b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgv6h9b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:page-included-filled" {...props}></Icon>
