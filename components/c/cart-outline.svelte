<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxf35rbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sxf35rbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-outline" {...props}></Icon>
