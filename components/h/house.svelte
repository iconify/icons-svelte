<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9fxkp7hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":840};
const content = `<path class="m9fxkp7hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:house" {...props}></Icon>
