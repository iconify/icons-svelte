<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr9hupbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yr9hupbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:jewellery-14" {...props}></Icon>
