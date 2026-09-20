<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvk3n9b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvk3n9b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:object-storage" {...props}></Icon>
