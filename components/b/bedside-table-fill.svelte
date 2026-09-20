<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvqbxfbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvqbxfbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bedside-table-fill" {...props}></Icon>
