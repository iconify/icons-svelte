<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_8zsnb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_8zsnb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:notepad-text-solid" {...props}></Icon>
