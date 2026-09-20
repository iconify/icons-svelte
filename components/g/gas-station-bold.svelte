<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3uxevb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z3uxevb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gas-station-bold" {...props}></Icon>
