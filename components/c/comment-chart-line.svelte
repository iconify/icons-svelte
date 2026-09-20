<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp3w_wbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp3w_wbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-chart-line" {...props}></Icon>
