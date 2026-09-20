<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxbt_k8yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxbt_k8yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-arrow-left" {...props}></Icon>
