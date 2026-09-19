<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa699oypj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa699oypj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bookmark-plus" {...props}></Icon>
