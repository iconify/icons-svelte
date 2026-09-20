<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ot6ubat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6ot6ubat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:bookmark" {...props}></Icon>
