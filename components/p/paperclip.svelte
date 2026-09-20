<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at0wybcon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="at0wybcon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:paperclip" {...props}></Icon>
