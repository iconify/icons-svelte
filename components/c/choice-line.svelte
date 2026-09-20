<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scf9pfbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scf9pfbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:choice-line" {...props}></Icon>
