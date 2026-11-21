<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyb13_mva.css';
import '../../css/g/go7uigb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jyb13_mva"/><path class="go7uigb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:codetta" {...props}></Icon>
