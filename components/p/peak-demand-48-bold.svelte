<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvxdc7lzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pvxdc7lzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:peak-demand-48-bold" {...props}></Icon>
