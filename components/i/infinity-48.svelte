<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttpm_-b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ttpm_-b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:infinity-48" {...props}></Icon>
