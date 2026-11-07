<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s00qodhty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s00qodhty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chart-line-down-16-solid" {...props}></Icon>
