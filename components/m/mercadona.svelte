<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahhv7fb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1130,"height":178};
const content = `<path class="ahhv7fb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mercadona" {...props}></Icon>
