<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei6tb3pbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ei6tb3pbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gauge-16-solid" {...props}></Icon>
