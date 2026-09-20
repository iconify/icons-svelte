<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctrl1fpbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctrl1fpbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cube-unfolded" {...props}></Icon>
