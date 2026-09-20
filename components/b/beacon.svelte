<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7gsv6u-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":93,"height":20};
const content = `<path clip-rule="evenodd" class="u7gsv6u-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:beacon" {...props}></Icon>
