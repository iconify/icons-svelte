<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oudmp2tzk.css';
import '../../css/y/y2ef2wbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="oudmp2tzk"/><path class="y2ef2wbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gatsby" {...props}></Icon>
