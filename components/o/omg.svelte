<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8cn0cczp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t8cn0cczp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:omg" {...props}></Icon>
