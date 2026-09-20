<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gguorqc5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gguorqc5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:loading" {...props}></Icon>
