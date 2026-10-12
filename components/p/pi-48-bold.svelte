<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg50c1boz.css';
import '../../css/w/wu5hif90s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zg50c1boz"/><path class="wu5hif90s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pi-48-bold" {...props}></Icon>
