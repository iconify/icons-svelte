<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr89lk6nk.css';
import '../../css/m/mli_10bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="zr89lk6nk"/><path class="mli_10bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:export" {...props}></Icon>
