<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubo8h4bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubo8h4bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:radio-heart" {...props}></Icon>
