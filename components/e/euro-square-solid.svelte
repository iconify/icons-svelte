<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbknc0bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbknc0bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:euro-square-solid" {...props}></Icon>
