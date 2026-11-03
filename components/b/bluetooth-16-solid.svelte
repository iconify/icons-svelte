<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bep6-31aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bep6-31aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bluetooth-16-solid" {...props}></Icon>
