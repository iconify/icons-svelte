<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r13jiwb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r13jiwb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rollerskates" {...props}></Icon>
