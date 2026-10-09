<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khd4an8mp.css';
import '../../css/d/dqca1ac-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="khd4an8mp"/><path class="dqca1ac-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biofuel-48-bold" {...props}></Icon>
