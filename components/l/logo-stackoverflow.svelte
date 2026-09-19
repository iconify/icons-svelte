<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f948t8o3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f948t8o3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-stackoverflow" {...props}></Icon>
