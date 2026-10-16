<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah3zxz6rp.css';
import '../../css/h/h_kmv8b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ah3zxz6rp"/><path class="h_kmv8b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chain-48" {...props}></Icon>
