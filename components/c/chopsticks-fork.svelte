<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efo1t8wme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="efo1t8wme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chopsticks-fork" {...props}></Icon>
