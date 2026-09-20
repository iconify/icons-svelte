<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3lwrccvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s3lwrccvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gps-compass-16" {...props}></Icon>
