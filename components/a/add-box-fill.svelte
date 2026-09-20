<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clmm-tbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clmm-tbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:add-box-fill" {...props}></Icon>
