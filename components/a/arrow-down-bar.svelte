<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7aos5bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7aos5bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-bar" {...props}></Icon>
