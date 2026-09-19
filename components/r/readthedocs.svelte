<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_k8d7bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s_k8d7bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:readthedocs" {...props}></Icon>
