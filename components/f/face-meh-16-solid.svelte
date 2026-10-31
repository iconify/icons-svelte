<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw-hmtx_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rw-hmtx_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-meh-16-solid" {...props}></Icon>
