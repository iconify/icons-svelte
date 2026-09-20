<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6xij5bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h6xij5bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:file-solid" {...props}></Icon>
