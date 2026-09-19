<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmt-9eb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dmt-9eb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bell-circle" {...props}></Icon>
