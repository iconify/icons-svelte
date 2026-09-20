<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb5txlixd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xb5txlixd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:google-solid" {...props}></Icon>
