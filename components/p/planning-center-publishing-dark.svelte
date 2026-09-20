<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5h931lea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5h931lea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-publishing-dark" {...props}></Icon>
