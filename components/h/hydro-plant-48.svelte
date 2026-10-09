<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4__ecb7c.css';
import '../../css/b/by5xuwclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d4__ecb7c"/><path class="by5xuwclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-48" {...props}></Icon>
