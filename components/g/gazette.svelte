<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep5ouyb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ep5ouyb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:gazette" {...props}></Icon>
