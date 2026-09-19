<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb61fbftd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nb61fbftd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:envelope-closed" {...props}></Icon>
