<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz50gn0rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz50gn0rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery" {...props}></Icon>
