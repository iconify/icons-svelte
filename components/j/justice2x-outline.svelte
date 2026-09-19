<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptp__nb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ptp__nb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:justice2x-outline" {...props}></Icon>
