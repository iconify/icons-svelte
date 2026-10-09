<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bibqapb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bibqapb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laptop-48-bold" {...props}></Icon>
