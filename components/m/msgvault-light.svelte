<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw__jkbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jw__jkbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:msgvault-light" {...props}></Icon>
