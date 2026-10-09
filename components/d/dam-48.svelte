<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm-2geb9q.css';
import '../../css/n/n33vuzbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mm-2geb9q"/><path class="n33vuzbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dam-48" {...props}></Icon>
