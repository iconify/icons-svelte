<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz4jzm5oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vz4jzm5oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:just" {...props}></Icon>
