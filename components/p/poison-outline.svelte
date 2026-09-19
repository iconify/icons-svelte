<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psoheuv8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="psoheuv8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:poison-outline" {...props}></Icon>
