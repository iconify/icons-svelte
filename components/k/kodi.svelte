<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/css75hbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="css75hbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:kodi" {...props}></Icon>
