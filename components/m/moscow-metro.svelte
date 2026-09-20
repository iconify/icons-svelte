<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf8t2ubeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf8t2ubeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:moscow-metro" {...props}></Icon>
