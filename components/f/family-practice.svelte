<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_lph5so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v3_lph5so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:family-practice" {...props}></Icon>
