<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/car149bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="car149bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:brightness-half" {...props}></Icon>
