<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjqdud4ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="vjqdud4ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-signature" {...props}></Icon>
