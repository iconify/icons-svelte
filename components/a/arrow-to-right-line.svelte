<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmmikzb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmmikzb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-to-right-line" {...props}></Icon>
