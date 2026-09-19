<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfsz-uvig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="sfsz-uvig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bicycle" {...props}></Icon>
