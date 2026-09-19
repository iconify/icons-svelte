<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcxr7fb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":446,"height":512};
const content = `<path class="rcxr7fb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rollup-old" {...props}></Icon>
