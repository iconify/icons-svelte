<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rge9qwkxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rge9qwkxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:redis" {...props}></Icon>
