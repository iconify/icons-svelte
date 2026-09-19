<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4t3_bbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4t3_bbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delivery-secure-01" {...props}></Icon>
