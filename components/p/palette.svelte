<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubnyel9uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubnyel9uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:palette" {...props}></Icon>
