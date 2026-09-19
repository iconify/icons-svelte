<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgbacacbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fgbacacbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cafe" {...props}></Icon>
