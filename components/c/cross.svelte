<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iokq22b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="iokq22b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cross" {...props}></Icon>
