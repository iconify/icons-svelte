<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv3ktebxk.css';
import '../../css/e/eq1ur8_nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mv3ktebxk"/><path class="eq1ur8_nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nginx" {...props}></Icon>
