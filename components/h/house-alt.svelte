<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/disp4rbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="disp4rbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:house-alt" {...props}></Icon>
