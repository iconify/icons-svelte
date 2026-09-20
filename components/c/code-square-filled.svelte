<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1j3dac_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j1j3dac_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:code-square-filled" {...props}></Icon>
