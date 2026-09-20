<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dllj3dbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dllj3dbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gemini" {...props}></Icon>
