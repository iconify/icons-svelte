<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpl4w9bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qpl4w9bmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fuelux" {...props}></Icon>
