<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohgar4mkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ohgar4mkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-ophthalmology" {...props}></Icon>
