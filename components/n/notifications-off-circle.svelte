<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arsnl03rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="arsnl03rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:notifications-off-circle" {...props}></Icon>
