<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx52wrbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xx52wrbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:birthday" {...props}></Icon>
