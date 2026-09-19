<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivvtuz9js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ivvtuz9js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:redo-circle-solid" {...props}></Icon>
