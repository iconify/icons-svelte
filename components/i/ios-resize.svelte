<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqz63jbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aqz63jbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-resize" {...props}></Icon>
