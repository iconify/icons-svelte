<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln0k-gcok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ln0k-gcok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-cleaning-48-bold" {...props}></Icon>
