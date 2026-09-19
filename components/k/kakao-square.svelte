<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htg2ctj4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="htg2ctj4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:kakao-square" {...props}></Icon>
