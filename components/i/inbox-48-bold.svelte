<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzc_knbku.css';
import '../../css/g/g-6zg3hle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tzc_knbku"/><path class="g-6zg3hle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inbox-48-bold" {...props}></Icon>
