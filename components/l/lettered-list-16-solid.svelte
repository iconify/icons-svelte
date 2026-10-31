<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehd_9cxzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ehd_9cxzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lettered-list-16-solid" {...props}></Icon>
