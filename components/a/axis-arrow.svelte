<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_zvc6bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_zvc6bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:axis-arrow" {...props}></Icon>
