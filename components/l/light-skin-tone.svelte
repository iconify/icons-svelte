<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9_cmhbvy.css';
import '../../css/y/yu8tkqs3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="q9_cmhbvy"/><path class="yu8tkqs3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:light-skin-tone" {...props}></Icon>
