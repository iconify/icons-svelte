<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd_v34b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hd_v34b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-accessibility" {...props}></Icon>
