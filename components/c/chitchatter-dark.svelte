<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9dlz72cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9dlz72cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chitchatter-dark" {...props}></Icon>
