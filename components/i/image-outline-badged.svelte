<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euf4rqbsc.css';
import '../../css/o/ofqyjfb8f.css';
import '../../css/o/osbfcbcig.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged euf4rqbsc"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged ofqyjfb8f"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged osbfcbcig"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-4--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:image-outline-badged" {...props}></Icon>
