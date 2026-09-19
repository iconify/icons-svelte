<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8_odj80p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8_odj80p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pin-alt" {...props}></Icon>
