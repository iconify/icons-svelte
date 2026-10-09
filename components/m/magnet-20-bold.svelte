<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkj35abos.css';
import '../../css/f/f_p8gj0ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jkj35abos"/><path class="f_p8gj0ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:magnet-20-bold" {...props}></Icon>
