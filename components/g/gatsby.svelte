<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru-ryy-1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ru-ryy-1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gatsby" {...props}></Icon>
