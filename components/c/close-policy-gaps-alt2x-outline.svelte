<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh9gwwb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rh9gwwb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:close-policy-gaps-alt2x-outline" {...props}></Icon>
