<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu2j1g89h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mu2j1g89h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-sad-hunappy" {...props}></Icon>
