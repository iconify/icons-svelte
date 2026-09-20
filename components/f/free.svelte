<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1rz05bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s1rz05bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:free" {...props}></Icon>
