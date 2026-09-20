<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb0x0e-xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb0x0e-xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:folder-multiple" {...props}></Icon>
