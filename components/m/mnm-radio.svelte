<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqcymg_vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqcymg_vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mnm-radio" {...props}></Icon>
