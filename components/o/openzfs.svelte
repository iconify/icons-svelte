<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je73ojbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="je73ojbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openzfs" {...props}></Icon>
