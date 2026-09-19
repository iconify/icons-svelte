<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb93p3fbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="vb93p3fbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mars" {...props}></Icon>
