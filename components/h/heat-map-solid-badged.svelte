<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4sw68-np.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--badged clr-i-solid-path-1--badged j4sw68-np"/><circle class="clr-i-badge clr-i-solid--badged clr-i-solid-path-22--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:heat-map-solid-badged" {...props}></Icon>
