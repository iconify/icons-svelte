<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t484tzbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t484tzbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:centrifuge-48-bold" {...props}></Icon>
