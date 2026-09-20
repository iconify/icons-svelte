<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izkbg5b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="izkbg5b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ngc-solid" {...props}></Icon>
