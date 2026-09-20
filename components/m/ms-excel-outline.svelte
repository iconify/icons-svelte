<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl9nb_96w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sl9nb_96w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ms-excel-outline" {...props}></Icon>
