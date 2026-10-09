<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvz99qbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvz99qbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flood-48-bold" {...props}></Icon>
