<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_am6mbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f_am6mbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:building" {...props}></Icon>
