<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh078gb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="rh078gb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cloud-down" {...props}></Icon>
