<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an6bpbblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="an6bpbblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-right-left-16-solid" {...props}></Icon>
