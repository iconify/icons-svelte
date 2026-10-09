<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy12kb2lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cy12kb2lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:menu-48-bold" {...props}></Icon>
