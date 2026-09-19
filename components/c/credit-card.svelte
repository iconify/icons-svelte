<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aexbrd5xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aexbrd5xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:credit-card" {...props}></Icon>
