<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6_t7vb5q.css';
import '../../css/k/ky_d4sbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w6_t7vb5q"/><path class="ky_d4sbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carabiner-48" {...props}></Icon>
