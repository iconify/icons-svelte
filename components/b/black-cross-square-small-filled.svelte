<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7pr7mgam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i7pr7mgam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-cross-square-small-filled" {...props}></Icon>
