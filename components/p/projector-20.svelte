<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi3_jwkbn.css';
import '../../css/z/zklarom7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mi3_jwkbn"/><path class="zklarom7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:projector-20" {...props}></Icon>
