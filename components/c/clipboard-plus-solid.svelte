<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv4r6ac-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vv4r6ac-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-plus-solid" {...props}></Icon>
