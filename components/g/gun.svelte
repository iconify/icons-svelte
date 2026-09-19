<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhcncsbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="hhcncsbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:gun" {...props}></Icon>
