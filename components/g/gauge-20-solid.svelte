<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv5akjb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rv5akjb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gauge-20-solid" {...props}></Icon>
