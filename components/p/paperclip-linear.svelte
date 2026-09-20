<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyfrh3d4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyfrh3d4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-linear" {...props}></Icon>
