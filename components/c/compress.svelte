<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8dght63r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":15};
const content = `<path class="u8dght63r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:compress" {...props}></Icon>
