<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plya-7jhm.css';
import '../../css/i/iurj758pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="plya-7jhm"/><path class="iurj758pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bee-48-bold" {...props}></Icon>
