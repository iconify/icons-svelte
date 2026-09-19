<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubmo3tbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ubmo3tbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:list-alt" {...props}></Icon>
