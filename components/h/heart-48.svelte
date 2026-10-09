<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsmyxibdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jsmyxibdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-48" {...props}></Icon>
