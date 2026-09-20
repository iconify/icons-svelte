<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kred8wbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kred8wbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-edit" {...props}></Icon>
