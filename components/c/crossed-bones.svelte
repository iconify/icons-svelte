<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me81uw3xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="me81uw3xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crossed-bones" {...props}></Icon>
