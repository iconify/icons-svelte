<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptycv73np.css';
import '../../css/d/d39hcpo6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ptycv73np"/><path class="d39hcpo6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:karma" {...props}></Icon>
