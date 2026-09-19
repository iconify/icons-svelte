<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyei_3bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="hyei_3bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:f055" {...props}></Icon>
