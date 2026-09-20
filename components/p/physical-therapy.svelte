<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qflhlgwkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qflhlgwkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:physical-therapy" {...props}></Icon>
