<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3pubybgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="i3pubybgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-arrow-path-20-solid" {...props}></Icon>
