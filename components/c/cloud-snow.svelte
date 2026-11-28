<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l45b1ings.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l45b1ings"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-snow" {...props}></Icon>
