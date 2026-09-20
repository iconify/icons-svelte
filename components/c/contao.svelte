<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w456m38wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w456m38wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:contao" {...props}></Icon>
