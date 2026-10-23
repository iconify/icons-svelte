<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odelaxbie.css';
import '../../css/w/wuhamvb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":400};
const content = `<path class="odelaxbie"/><path class="wuhamvb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:backloggd" {...props}></Icon>
