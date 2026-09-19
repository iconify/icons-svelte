<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs4bnbc_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs4bnbc_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:remove-cart" {...props}></Icon>
