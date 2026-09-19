<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjox5-scv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bjox5-scv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:align-justify" {...props}></Icon>
