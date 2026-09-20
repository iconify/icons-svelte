<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3hw_dbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m3hw_dbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:inbox-complete-solid" {...props}></Icon>
