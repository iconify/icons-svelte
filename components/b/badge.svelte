<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_1j6lb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_1j6lb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:badge" {...props}></Icon>
