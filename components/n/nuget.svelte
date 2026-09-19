<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5uzvqogd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l5uzvqogd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nuget" {...props}></Icon>
