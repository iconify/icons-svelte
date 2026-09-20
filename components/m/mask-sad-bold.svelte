<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-2dukbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i-2dukbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mask-sad-bold" {...props}></Icon>
