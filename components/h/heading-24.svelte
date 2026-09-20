<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2p5vab0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2p5vab0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:heading-24" {...props}></Icon>
