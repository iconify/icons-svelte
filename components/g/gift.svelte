<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdt6c6bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tdt6c6bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:gift" {...props}></Icon>
