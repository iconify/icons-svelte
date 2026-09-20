<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a05-frb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a05-frb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:download-16" {...props}></Icon>
