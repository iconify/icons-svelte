<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0bashbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1280};
const content = `<path class="q0bashbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:minus" {...props}></Icon>
