<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obj86qm_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="obj86qm_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:desktop-alt" {...props}></Icon>
