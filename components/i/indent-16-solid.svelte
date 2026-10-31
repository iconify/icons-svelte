<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt8_6yb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yt8_6yb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent-16-solid" {...props}></Icon>
