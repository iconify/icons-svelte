<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-cg9db9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n-cg9db9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-small-down" {...props}></Icon>
