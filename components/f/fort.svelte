<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0y37gbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0y37gbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fort" {...props}></Icon>
