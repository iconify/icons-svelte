<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghffgtezg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghffgtezg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:present-open" {...props}></Icon>
