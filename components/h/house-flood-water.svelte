<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_899058x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="s_899058x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-flood-water" {...props}></Icon>
