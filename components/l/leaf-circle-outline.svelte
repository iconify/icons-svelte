<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xay_q6mqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xay_q6mqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:leaf-circle-outline" {...props}></Icon>
