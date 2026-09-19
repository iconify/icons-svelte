<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb7732w4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wb7732w4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:negative-negative" {...props}></Icon>
