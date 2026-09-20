<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evl32sbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evl32sbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mom" {...props}></Icon>
