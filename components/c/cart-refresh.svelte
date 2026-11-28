<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh7f7tbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh7f7tbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cart-refresh" {...props}></Icon>
