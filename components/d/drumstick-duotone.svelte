<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxtpogbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary uxtpogbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drumstick-duotone" {...props}></Icon>
