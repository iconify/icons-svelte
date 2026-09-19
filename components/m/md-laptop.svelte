<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avrmeeqly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="avrmeeqly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-laptop" {...props}></Icon>
