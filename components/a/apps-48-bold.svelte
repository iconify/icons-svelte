<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0g8a-baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r0g8a-baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apps-48-bold" {...props}></Icon>
