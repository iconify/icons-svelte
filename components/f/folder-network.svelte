<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idk8i0bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idk8i0bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-network" {...props}></Icon>
