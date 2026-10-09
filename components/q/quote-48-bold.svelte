<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/una0qyech.css';
import '../../css/g/gzmmb_5vu.css';
import '../../css/x/x5dd3rcaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="una0qyech"/><path class="gzmmb_5vu"/><path class="x5dd3rcaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:quote-48-bold" {...props}></Icon>
