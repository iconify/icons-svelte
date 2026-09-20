<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scn5v8bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="scn5v8bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dice-16-solid" {...props}></Icon>
