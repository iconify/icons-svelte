<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hftpl1bgl.css';
import '../../css/l/lq8j-ubmb.css';
import '../../css/a/ay3n_xfrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hftpl1bgl"/><path class="lq8j-ubmb"/><path class="ay3n_xfrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:robot" {...props}></Icon>
