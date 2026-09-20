<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uog1-9bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uog1-9bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agregarr-dark" {...props}></Icon>
