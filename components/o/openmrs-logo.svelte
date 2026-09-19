<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bir3djc_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bir3djc_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:openmrs-logo" {...props}></Icon>
