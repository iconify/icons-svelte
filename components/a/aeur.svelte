<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuevp5inu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xuevp5inu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:aeur" {...props}></Icon>
