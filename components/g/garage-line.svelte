<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe_3scbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe_3scbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:garage-line" {...props}></Icon>
