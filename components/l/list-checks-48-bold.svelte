<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh7ndob2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wh7ndob2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-checks-48-bold" {...props}></Icon>
