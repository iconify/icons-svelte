<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8d4-cc9w.css';
import '../../css/p/p8mr26bfo.css';
import '../../css/g/g4j5pwbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8d4-cc9w"/><path clip-rule="evenodd" class="p8mr26bfo"/><path class="g4j5pwbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-bold-duotone" {...props}></Icon>
