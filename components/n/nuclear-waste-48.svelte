<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-flw2bql.css';
import '../../css/x/x-3i40bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m-flw2bql"/><path class="x-3i40bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-waste-48" {...props}></Icon>
