<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vigb5_xuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":220,"height":62};
const content = `<path class="vigb5_xuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:onshape" {...props}></Icon>
