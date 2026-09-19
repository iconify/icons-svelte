<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd9s1h7jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yd9s1h7jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-data-sync" {...props}></Icon>
