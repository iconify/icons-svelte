<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqw0eob9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqw0eob9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-volume-down" {...props}></Icon>
