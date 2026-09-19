<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb1mrmbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wb1mrmbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-in-design" {...props}></Icon>
