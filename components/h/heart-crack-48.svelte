<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsmyxibdu.css';
import '../../css/f/fywdbmb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jsmyxibdu"/><path class="fywdbmb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-crack-48" {...props}></Icon>
