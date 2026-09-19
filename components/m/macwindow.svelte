<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3a5pqxdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u3a5pqxdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:macwindow" {...props}></Icon>
