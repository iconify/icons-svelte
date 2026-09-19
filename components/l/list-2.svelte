<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqjkksdmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="vqjkksdmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:list-2" {...props}></Icon>
