<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzhwxisqb.css';
import '../../css/o/ocwcvp2hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pzhwxisqb"/><path class="ocwcvp2hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dehumidifier-48-bold" {...props}></Icon>
