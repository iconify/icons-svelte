<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0hdegj7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0hdegj7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-blank-off-outline" {...props}></Icon>
