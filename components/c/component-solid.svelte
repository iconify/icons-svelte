<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-yd0b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie-yd0b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:component-solid" {...props}></Icon>
