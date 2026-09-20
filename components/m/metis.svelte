<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr7wbsbom.css';
import '../../css/x/xlp5pbcfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr7wbsbom"/><path class="xlp5pbcfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:metis" {...props}></Icon>
