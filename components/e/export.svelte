<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjtc9yosc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vjtc9yosc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:export" {...props}></Icon>
