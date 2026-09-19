<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsjtpacxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xsjtpacxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-bottom-right-center-8" {...props}></Icon>
