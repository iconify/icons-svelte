<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4eww14cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c4eww14cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:glinr" {...props}></Icon>
