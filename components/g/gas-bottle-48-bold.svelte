<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2mawalq.css';
import '../../css/v/vzv6lusvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eb2mawalq"/><path class="vzv6lusvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-bottle-48-bold" {...props}></Icon>
