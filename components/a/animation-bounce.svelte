<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnccf7btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnccf7btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:animation-bounce" {...props}></Icon>
