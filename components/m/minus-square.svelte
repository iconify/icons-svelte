<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0yquubfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0yquubfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:minus-square" {...props}></Icon>
