<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgxqqcc2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="qgxqqcc2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:livejournal" {...props}></Icon>
