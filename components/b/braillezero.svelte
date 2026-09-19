<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8kj_6bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="a8kj_6bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillezero" {...props}></Icon>
