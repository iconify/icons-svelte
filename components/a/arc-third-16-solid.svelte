<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhkjd6b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhkjd6b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arc-third-16-solid" {...props}></Icon>
