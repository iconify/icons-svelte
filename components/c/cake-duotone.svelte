<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sq304gt3i.css';
import '../../css/a/a7fo8bbwo.css';
import '../../css/b/bue9mkoxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sq304gt3i"/><path class="a7fo8bbwo"/><path class="bue9mkoxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cake-duotone" {...props}></Icon>
