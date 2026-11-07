<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7e0u3hqa.css';
import '../../css/p/plovyotpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7e0u3hqa"/><path clip-rule="evenodd" class="plovyotpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-minimalistic-close-outline" {...props}></Icon>
