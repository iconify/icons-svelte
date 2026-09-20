<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvai0mk5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fvai0mk5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:golf" {...props}></Icon>
