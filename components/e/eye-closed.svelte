<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c01l0ubzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c01l0ubzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:eye-closed" {...props}></Icon>
