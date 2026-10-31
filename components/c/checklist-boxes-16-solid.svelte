<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdp6b9bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rdp6b9bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:checklist-boxes-16-solid" {...props}></Icon>
