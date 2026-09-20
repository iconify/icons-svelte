<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7b_bhb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="x7b_bhb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:map-pin-5" {...props}></Icon>
