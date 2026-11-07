<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl66i7bqg.css';
import '../../css/x/x-5f2htjo.css';
import '../../css/y/yfcobkb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="x-5f2htjo"/><path clip-rule="evenodd" class="yfcobkb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-bug-bold-duotone" {...props}></Icon>
