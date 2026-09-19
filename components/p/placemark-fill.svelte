<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uetza5byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uetza5byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:placemark-fill" {...props}></Icon>
