<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz046pbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lz046pbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-right-left-16-solid" {...props}></Icon>
