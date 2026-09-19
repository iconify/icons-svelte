<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6m59nb7p.css';
import '../../css/y/yyfpz7bxh.css';
import '../../css/o/oiejv2yqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6m59nb7p"/><path class="yyfpz7bxh"/><path class="oiejv2yqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-doc" {...props}></Icon>
