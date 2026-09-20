<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx5d-bc1s.css';
import '../../css/b/boywt1bng.css';
import '../../css/r/rebbjcb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nx5d-bc1s"><path class="boywt1bng"/><path class="rebbjcb_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:flux-black-forest-labs" {...props}></Icon>
