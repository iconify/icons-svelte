<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpp3nrb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hpp3nrb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moonset-48-bold" {...props}></Icon>
