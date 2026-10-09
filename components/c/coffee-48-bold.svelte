<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqabahbkv.css';
import '../../css/a/awqfydw7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rqabahbkv"/><path class="awqfydw7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coffee-48-bold" {...props}></Icon>
