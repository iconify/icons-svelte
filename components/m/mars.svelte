<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5n1f5bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="g5n1f5bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mars" {...props}></Icon>
