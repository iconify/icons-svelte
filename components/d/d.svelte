<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du_u15bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="du_u15bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:d" {...props}></Icon>
