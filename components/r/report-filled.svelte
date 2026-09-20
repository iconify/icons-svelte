<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu-gg3pdt.css';
import '../../css/m/mk0qhjb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vu-gg3pdt"/><path class="mk0qhjb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:report-filled" {...props}></Icon>
