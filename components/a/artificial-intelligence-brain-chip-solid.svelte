<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utb4tgbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="utb4tgbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:artificial-intelligence-brain-chip-solid" {...props}></Icon>
