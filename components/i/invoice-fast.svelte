<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg8eb8y-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg8eb8y-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-fast" {...props}></Icon>
