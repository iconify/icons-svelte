<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfi5rmbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vfi5rmbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:line-fault-48-bold" {...props}></Icon>
