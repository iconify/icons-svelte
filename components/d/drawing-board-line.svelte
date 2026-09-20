<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfgzsf_mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgzsf_mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drawing-board-line" {...props}></Icon>
