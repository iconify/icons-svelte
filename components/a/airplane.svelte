<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh7r9_dwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh7r9_dwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:airplane" {...props}></Icon>
