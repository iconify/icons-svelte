<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aofe76cbq.css';
import '../../css/g/gxgezbb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aofe76cbq"/><path class="gxgezbb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:interconnector-48-bold" {...props}></Icon>
