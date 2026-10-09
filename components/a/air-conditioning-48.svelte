<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3-w5po8z.css';
import '../../css/k/kyspg4brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3-w5po8z"/><path class="kyspg4brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioning-48" {...props}></Icon>
