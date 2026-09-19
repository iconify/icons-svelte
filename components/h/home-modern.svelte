<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/solu_m_dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="solu_m_dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:home-modern" {...props}></Icon>
