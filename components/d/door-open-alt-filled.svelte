<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnh_arkbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnh_arkbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:door-open-alt-filled" {...props}></Icon>
