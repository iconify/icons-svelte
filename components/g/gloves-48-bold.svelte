<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7de_1bdc.css';
import '../../css/d/djawiyg4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p7de_1bdc"/><path class="djawiyg4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gloves-48-bold" {...props}></Icon>
