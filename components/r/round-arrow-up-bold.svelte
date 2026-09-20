<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzozlkfxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzozlkfxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-up-bold" {...props}></Icon>
