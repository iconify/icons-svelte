<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-uqfkbjc.css';
import '../../css/y/yql3_6e3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-uqfkbjc"/><path clip-rule="evenodd" class="yql3_6e3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-4-outline" {...props}></Icon>
