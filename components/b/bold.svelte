<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoemicr0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="hoemicr0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bold" {...props}></Icon>
