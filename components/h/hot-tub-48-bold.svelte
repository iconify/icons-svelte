<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lelyizmit.css';
import '../../css/s/spkgakbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lelyizmit"/><path class="spkgakbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-tub-48-bold" {...props}></Icon>
