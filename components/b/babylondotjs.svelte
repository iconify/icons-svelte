<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_g3u5eqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_g3u5eqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:babylondotjs" {...props}></Icon>
