<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecex6lblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecex6lblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-brush-fill" {...props}></Icon>
