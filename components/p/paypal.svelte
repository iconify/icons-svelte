<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfo1k5b-e.css';
import '../../css/n/nlqvrrg1h.css';
import '../../css/n/nniesdbig.css';
import '../../css/j/jaw_f2b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":14};
const content = `<path class="sfo1k5b-e"/><path class="nlqvrrg1h"/><path class="nniesdbig"/><path class="jaw_f2b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:paypal" {...props}></Icon>
