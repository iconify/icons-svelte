<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn8ho2_yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn8ho2_yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:reader" {...props}></Icon>
