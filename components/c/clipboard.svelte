<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtv-ejb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="jtv-ejb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:clipboard" {...props}></Icon>
