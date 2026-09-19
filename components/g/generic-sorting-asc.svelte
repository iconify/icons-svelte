<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al-qozjuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="al-qozjuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:generic-sorting-asc" {...props}></Icon>
