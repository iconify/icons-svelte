<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzta2cbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="kzta2cbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:meh-rolling-eyes" {...props}></Icon>
