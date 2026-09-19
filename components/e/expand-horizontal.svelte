<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy-badc1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy-badc1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:expand-horizontal" {...props}></Icon>
