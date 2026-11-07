<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8nox1bbt.css';
import '../../css/o/ouxb72b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z8nox1bbt"/><path class="ouxb72b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-minimalistic-bold-duotone" {...props}></Icon>
