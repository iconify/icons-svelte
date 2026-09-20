<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3xkf5b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3xkf5b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-light" {...props}></Icon>
