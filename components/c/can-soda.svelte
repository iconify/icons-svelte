<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfe2m2bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfe2m2bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:can-soda" {...props}></Icon>
