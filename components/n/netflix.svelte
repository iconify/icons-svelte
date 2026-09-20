<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn1wrwb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jn1wrwb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:netflix" {...props}></Icon>
