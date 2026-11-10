<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5n5_gptj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5n5_gptj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-arrow-path-16-solid" {...props}></Icon>
