<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldi8w1b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldi8w1b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:notion" {...props}></Icon>
