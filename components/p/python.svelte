<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki8vug_cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ki8vug_cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:python" {...props}></Icon>
