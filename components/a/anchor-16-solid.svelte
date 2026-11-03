<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib8logbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ib8logbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:anchor-16-solid" {...props}></Icon>
