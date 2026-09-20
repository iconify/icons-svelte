<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1_2kycla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1_2kycla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:btc-fill" {...props}></Icon>
