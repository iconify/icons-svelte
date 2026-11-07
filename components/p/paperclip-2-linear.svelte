<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whzycacat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whzycacat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-2-linear" {...props}></Icon>
