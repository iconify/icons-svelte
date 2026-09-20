<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or4mibcim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="or4mibcim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:goaccess-dark" {...props}></Icon>
