<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lttya_ivm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lttya_ivm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-remove-outline" {...props}></Icon>
