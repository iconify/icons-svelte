<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtwdebc9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dtwdebc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:info-circle" {...props}></Icon>
