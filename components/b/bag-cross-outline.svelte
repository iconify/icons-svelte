<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfm8lbbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vfm8lbbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-cross-outline" {...props}></Icon>
