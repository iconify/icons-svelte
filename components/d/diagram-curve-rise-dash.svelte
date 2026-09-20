<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q42vlfw3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q42vlfw3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-curve-rise-dash" {...props}></Icon>
