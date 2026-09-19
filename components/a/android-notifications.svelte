<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7sfj1b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7sfj1b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-notifications" {...props}></Icon>
