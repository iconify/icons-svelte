<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrx4xb-sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrx4xb-sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-three-solid" {...props}></Icon>
