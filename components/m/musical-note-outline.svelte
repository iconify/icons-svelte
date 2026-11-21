<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y04k47f9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y04k47f9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:musical-note-outline" {...props}></Icon>
