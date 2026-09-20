<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfuzbjb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gfuzbjb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-surgery" {...props}></Icon>
