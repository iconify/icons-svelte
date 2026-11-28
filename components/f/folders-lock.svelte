<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9x1_l0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9x1_l0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folders-lock" {...props}></Icon>
