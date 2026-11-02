<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/relhjsb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="relhjsb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-locked-line" {...props}></Icon>
