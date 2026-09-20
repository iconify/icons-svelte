<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czzhiui1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czzhiui1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:iterations-24" {...props}></Icon>
