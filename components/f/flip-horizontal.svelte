<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzdgkcc2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzdgkcc2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flip-horizontal" {...props}></Icon>
