<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2o5wdb0f.css';
import '../../css/g/gbgl6tbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u2o5wdb0f"/><path class="gbgl6tbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:history-48-bold" {...props}></Icon>
