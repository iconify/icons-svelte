<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldh_0wm7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ldh_0wm7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:plus-square-on-square" {...props}></Icon>
