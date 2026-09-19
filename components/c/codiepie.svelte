<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c61p-ac-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1792};
const content = `<path class="c61p-ac-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:codiepie" {...props}></Icon>
