<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-5f2htjo.css';
import '../../css/o/o19b52bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-5f2htjo"/><path clip-rule="evenodd" class="o19b52bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-check-bold" {...props}></Icon>
