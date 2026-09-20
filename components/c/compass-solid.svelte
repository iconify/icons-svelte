<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y63y_obeb.css';
import '../../css/i/ixud4xmsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y63y_obeb"/><path clip-rule="evenodd" class="ixud4xmsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:compass-solid" {...props}></Icon>
