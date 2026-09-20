<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctml66e9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctml66e9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:flame-24" {...props}></Icon>
