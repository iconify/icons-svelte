<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i001kvvwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i001kvvwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:justify-center-16" {...props}></Icon>
