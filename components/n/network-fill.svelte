<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_5nsrb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_5nsrb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:network-fill" {...props}></Icon>
