<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6jl-3b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":612,"height":90.8,"top":350.6};
const content = `<path class="f6jl-3b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:funimation" {...props}></Icon>
