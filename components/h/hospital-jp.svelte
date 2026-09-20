<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhx4xggnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zhx4xggnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hospital-jp" {...props}></Icon>
