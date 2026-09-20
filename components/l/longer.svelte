<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_t18m0xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_t18m0xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:longer" {...props}></Icon>
