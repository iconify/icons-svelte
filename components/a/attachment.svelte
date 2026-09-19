<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lehfdhbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":470,"height":850};
const content = `<path class="lehfdhbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:attachment" {...props}></Icon>
