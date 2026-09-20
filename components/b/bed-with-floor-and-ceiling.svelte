<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr9hqtbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tr9hqtbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bed-with-floor-and-ceiling" {...props}></Icon>
