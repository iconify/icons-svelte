<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlr6cy_uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlr6cy_uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:backspace" {...props}></Icon>
