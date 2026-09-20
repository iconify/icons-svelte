<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw9n2obat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw9n2obat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contract-right-fill" {...props}></Icon>
