<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzznv0gvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzznv0gvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:headphones" {...props}></Icon>
