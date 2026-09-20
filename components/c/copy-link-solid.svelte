<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln3utrbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln3utrbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:copy-link-solid" {...props}></Icon>
