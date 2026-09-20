<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp270sbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bp270sbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cat" {...props}></Icon>
