<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8o5yujab.css';
import '../../css/q/qdez92c3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r8o5yujab"/><path class="qdez92c3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-dual-48" {...props}></Icon>
