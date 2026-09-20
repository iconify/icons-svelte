<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unxhmtuvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unxhmtuvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drum-line" {...props}></Icon>
