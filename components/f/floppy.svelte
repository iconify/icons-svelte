<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5o_g32uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h5o_g32uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:floppy" {...props}></Icon>
