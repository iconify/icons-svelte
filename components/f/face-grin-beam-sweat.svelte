<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdci4xqph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdci4xqph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grin-beam-sweat" {...props}></Icon>
