<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox2p3pbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ox2p3pbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rect" {...props}></Icon>
