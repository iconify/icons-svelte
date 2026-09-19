<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr41qglch.css';
import '../../css/y/yph1tgb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr41qglch"/><path class="yph1tgb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-left-stroke-circle-half-filled" {...props}></Icon>
