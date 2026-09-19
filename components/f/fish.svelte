<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n42l-qbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="n42l-qbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fish" {...props}></Icon>
