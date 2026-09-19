<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coj1sq9ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="coj1sq9ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:circle-thin" {...props}></Icon>
