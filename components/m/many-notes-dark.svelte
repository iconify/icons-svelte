<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unfhlwjsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unfhlwjsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:many-notes-dark" {...props}></Icon>
