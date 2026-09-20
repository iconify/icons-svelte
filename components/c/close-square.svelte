<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tic2qubla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tic2qubla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:close-square" {...props}></Icon>
