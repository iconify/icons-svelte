<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beni0rbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beni0rbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-linear" {...props}></Icon>
