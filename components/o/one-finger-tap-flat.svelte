<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iod-m7bxe.css';
import '../../css/b/bpu_dobxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="iod-m7bxe"/><path clip-rule="evenodd" class="bpu_dobxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:one-finger-tap-flat" {...props}></Icon>
