<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfo7wmb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfo7wmb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:order-adjustment-column" {...props}></Icon>
