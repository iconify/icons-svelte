<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nekdegzbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nekdegzbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:ai-chip-robot-solid" {...props}></Icon>
