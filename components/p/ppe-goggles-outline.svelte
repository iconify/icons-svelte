<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrqcf-bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mrqcf-bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-goggles-outline" {...props}></Icon>
