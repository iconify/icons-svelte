<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_bf9cbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_bf9cbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-percent" {...props}></Icon>
